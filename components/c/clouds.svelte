<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ya2h7zbxa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ya2h7zbxa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="doodle-icons:clouds" {...props}></Icon>
