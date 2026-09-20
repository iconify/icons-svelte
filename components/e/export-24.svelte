<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s3ez0xyqh.css';
import '../../css/b/bnmfd8bdw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s3ez0xyqh"/><path class="bnmfd8bdw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:export-24" {...props}></Icon>
