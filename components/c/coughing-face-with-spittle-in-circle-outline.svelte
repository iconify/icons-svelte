<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q1igjb5bq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="q1igjb5bq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:coughing-face-with-spittle-in-circle-outline" {...props}></Icon>
