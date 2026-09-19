<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ajbs2lbjq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":36,"height":24};
const content = `<path class="ajbs2lbjq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:jcb" {...props}></Icon>
