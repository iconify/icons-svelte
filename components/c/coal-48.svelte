<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q70bmjh4f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="q70bmjh4f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:coal-48" {...props}></Icon>
