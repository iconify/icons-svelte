<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/stu8cqb7t.css';
import '../../css/c/c485hsbmk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="stu8cqb7t"/><path class="c485hsbmk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:diff-added-24" {...props}></Icon>
