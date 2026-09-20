<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hqmyt4erw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hqmyt4erw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:planetscale" {...props}></Icon>
