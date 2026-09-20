<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/df5fzub9i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="df5fzub9i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:option-a" {...props}></Icon>
