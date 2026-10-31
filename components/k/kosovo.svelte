<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e8dybub9u.css';
import '../../css/u/utquofbms.css';
import '../../css/z/zbsqqabff.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":24};
const content = `<path class="e8dybub9u"/><path class="utquofbms"/><path class="zbsqqabff"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler-flags:kosovo" {...props}></Icon>
