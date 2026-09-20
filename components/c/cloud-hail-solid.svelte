<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bbr6a_bem.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bbr6a_bem"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:cloud-hail-solid" {...props}></Icon>
