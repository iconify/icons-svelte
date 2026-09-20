<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gwt7dmi2n.css';
import '../../css/c/c8k9rbbql.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="gwt7dmi2n"/><path class="c8k9rbbql"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:check-square-o" {...props}></Icon>
