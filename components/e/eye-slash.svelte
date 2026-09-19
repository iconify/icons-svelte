<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mni_8lbgr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mni_8lbgr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-outline:eye-slash" {...props}></Icon>
