<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kxqmg7esw.css';
import '../../css/s/s7gdozb6t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="kxqmg7esw"/><path class="s7gdozb6t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:lightbulb" {...props}></Icon>
