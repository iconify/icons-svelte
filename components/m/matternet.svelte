<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hyy6gn3df.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="hyy6gn3df"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:matternet" {...props}></Icon>
