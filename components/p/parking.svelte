<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/otzh3hbtm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="otzh3hbtm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="guidance:parking" {...props}></Icon>
