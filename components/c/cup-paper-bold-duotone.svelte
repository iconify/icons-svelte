<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o_o-wt13s.css';
import '../../css/j/jrfk4909t.css';
import '../../css/u/u23ewcsgh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o_o-wt13s"/><path class="jrfk4909t"/><path class="u23ewcsgh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:cup-paper-bold-duotone" {...props}></Icon>
