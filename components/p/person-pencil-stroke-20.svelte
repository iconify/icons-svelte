<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q8wenfbcs.css';
import '../../css/o/o4xm8u5yr.css';
import '../../css/a/a9k_5nb9t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="q8wenfbcs"/><path class="o4xm8u5yr"/><path class="a9k_5nb9t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:person-pencil-stroke-20" {...props}></Icon>
