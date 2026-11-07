<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k89onwb0c.css';
import '../../css/l/lr49xfj0d.css';
import '../../css/o/o4hc_dhel.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k89onwb0c"/><path clip-rule="evenodd" class="lr49xfj0d"/><path clip-rule="evenodd" class="o4hc_dhel"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:medical-kit-outline" {...props}></Icon>
