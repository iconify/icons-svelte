<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/ghswe8lyk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ghswe8lyk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:qiita" {...props}></Icon>
