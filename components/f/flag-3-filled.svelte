<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ak6i94bci.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ak6i94bci"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:flag-3-filled" {...props}></Icon>
