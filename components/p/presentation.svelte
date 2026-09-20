<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/svz5apblp.css';
import '../../css/s/sk_7s2z0a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="svz5apblp"/><path class="sk_7s2z0a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:presentation" {...props}></Icon>
