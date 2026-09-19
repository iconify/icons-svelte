<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jpmpq7j_v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="jpmpq7j_v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:circlestopempty" {...props}></Icon>
