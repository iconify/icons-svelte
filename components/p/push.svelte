<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fjbue95vu.css';
import '../../css/z/zpecffw0q.css';
import '../../css/w/w8qc-tbhs.css';
import '../../css/s/si0qb1owb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fjbue95vu"/><path class="zpecffw0q"/><path class="w8qc-tbhs"/><path class="si0qb1owb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:push" {...props}></Icon>
