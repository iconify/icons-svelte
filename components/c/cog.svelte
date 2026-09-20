<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c2ng3jt7l.css';
import '../../css/j/j6bkybbuh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="c2ng3jt7l"/><path class="j6bkybbuh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:cog" {...props}></Icon>
