<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ebxc1ccgv.css';
import '../../css/g/gwken0w2c.css';
import '../../css/s/sy_a5lx3l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ebxc1ccgv"/><path clip-rule="evenodd" class="gwken0w2c"/><path clip-rule="evenodd" class="sy_a5lx3l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cuida:lifebuoy-outline" {...props}></Icon>
