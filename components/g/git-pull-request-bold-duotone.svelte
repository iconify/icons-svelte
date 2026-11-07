<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r5qboab5t.css';
import '../../css/o/oeh5lxbqa.css';
import '../../css/p/p03812bxn.css';
import '../../css/m/mnelrmb_n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r5qboab5t"/><path clip-rule="evenodd" class="oeh5lxbqa"/><path clip-rule="evenodd" class="p03812bxn"/><path clip-rule="evenodd" class="mnelrmb_n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:git-pull-request-bold-duotone" {...props}></Icon>
