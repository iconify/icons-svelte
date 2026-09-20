<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bp348r2av.css';
import '../../css/j/jfqxk9a8y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bp348r2av"/><path class="jfqxk9a8y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:chart-pie-duotone" {...props}></Icon>
