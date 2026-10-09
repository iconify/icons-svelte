<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rekkswb7u.css';
import '../../css/f/f1fwzpb3n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="rekkswb7u"/><path class="f1fwzpb3n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:credit-card-20" {...props}></Icon>
