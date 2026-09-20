<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/intqmzodw.css';
import '../../css/j/jbvtufb0o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="intqmzodw"/><path class="jbvtufb0o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:outbox" {...props}></Icon>
