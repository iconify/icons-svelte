<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cw3q3-91j.css';
import '../../css/z/zo8llxvbi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cw3q3-91j duoicon-secondary-layer"/><path class="duoicon-primary-layer zo8llxvbi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="duo-icons:campground" {...props}></Icon>
