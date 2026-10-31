<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z_rr6xiqh.css';
import '../../css/l/lejmcbbfw.css';
import '../../css/o/oui96b1vm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<g display="block"><path class="z_rr6xiqh"/><path class="lejmcbbfw"/><path class="oui96b1vm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconito:egg" {...props}></Icon>
