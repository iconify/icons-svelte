<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qw1zzn-6t.css';
import '../../css/r/ra2ravfoj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qw1zzn-6t"/><path class="ra2ravfoj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:dumbbells-2-bold" {...props}></Icon>
