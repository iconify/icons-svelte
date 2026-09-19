<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ud2t_6b-y.css';
import '../../css/h/hxggj4dhe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="ud2t_6b-y"/><path class="hxggj4dhe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="foundation:clock" {...props}></Icon>
