<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v9hw_hbtw.css';
import '../../css/j/jej-4abki.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="v9hw_hbtw"/><path class="jej-4abki"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:character-whole-number" {...props}></Icon>
