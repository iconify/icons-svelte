<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n3hxf6ffp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n3hxf6ffp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:main-component2" {...props}></Icon>
