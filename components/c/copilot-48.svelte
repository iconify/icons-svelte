<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hdh5ety7c.css';
import '../../css/k/ktbpolgkg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="hdh5ety7c"/><path class="ktbpolgkg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:copilot-48" {...props}></Icon>
