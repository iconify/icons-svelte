<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/anz_yn18j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="anz_yn18j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-outline:briefcase" {...props}></Icon>
