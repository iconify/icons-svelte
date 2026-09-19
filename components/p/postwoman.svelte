<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x7gqf0y9i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="x7gqf0y9i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:postwoman" {...props}></Icon>
