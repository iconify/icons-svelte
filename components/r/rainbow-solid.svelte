<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xi0bh4bum.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xi0bh4bum"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:rainbow-solid" {...props}></Icon>
