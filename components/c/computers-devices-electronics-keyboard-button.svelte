<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fs_t-dgjs.css';
import '../../css/b/b_zpflbco.css';
import '../../css/g/gt8ehhy9i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="fs_t-dgjs"/><path class="b_zpflbco"/><path class="gt8ehhy9i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:computers-devices-electronics-keyboard-button" {...props}></Icon>
