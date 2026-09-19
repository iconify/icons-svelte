<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/emylgjb0y.css';
import '../../css/r/rbak6zq5p.css';
import '../../css/z/zxys3pw6q.css';
import '../../css/z/zkwmf0bbe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<defs/><path class="emylgjb0y"/><path class="rbak6zq5p"/><path class="zxys3pw6q"/><path class="zkwmf0bbe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:barrier" {...props}></Icon>
