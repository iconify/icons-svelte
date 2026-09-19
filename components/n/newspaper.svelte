<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bbw7jyfci.css';
import '../../css/e/ebwjynfzt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bbw7jyfci"/><path class="ebwjynfzt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:newspaper" {...props}></Icon>
