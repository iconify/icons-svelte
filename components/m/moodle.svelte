<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hjr4ghz5f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hjr4ghz5f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:moodle" {...props}></Icon>
