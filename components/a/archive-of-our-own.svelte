<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ya8gu7fuq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ya8gu7fuq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:archive-of-our-own" {...props}></Icon>
