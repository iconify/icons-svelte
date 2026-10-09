<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tbyd0vbew.css';
import '../../css/b/bhk7a-jqs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="tbyd0vbew"/><path class="bhk7a-jqs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:corner-up-left-48-bold" {...props}></Icon>
