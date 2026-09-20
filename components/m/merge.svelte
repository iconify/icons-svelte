<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qef9l7bhw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":40,"height":40};
const content = `<path class="qef9l7bhw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iwwa:merge" {...props}></Icon>
