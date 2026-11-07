<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q6vco797o.css';
import '../../css/l/lkfeoqf6r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q6vco797o"/><path clip-rule="evenodd" class="lkfeoqf6r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:health-outline" {...props}></Icon>
