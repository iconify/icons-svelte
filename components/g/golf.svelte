<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q9u8tbcym.css';
import '../../css/o/o_4vtebcc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="q9u8tbcym"/><path class="o_4vtebcc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:golf" {...props}></Icon>
