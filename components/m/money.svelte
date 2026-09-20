<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j2sfk-bes.css';
import '../../css/a/ajxq6raqs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="j2sfk-bes"/><path class="ajxq6raqs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:money" {...props}></Icon>
