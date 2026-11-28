<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r5fe-rb_f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r5fe-rb_f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:database-question" {...props}></Icon>
