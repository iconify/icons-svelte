<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d7cj0jbqm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="d7cj0jbqm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:f-12-dev-tools" {...props}></Icon>
