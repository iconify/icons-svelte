<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v1g1yybko.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":30};
const content = `<path class="v1g1yybko"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wi:moon-13" {...props}></Icon>
