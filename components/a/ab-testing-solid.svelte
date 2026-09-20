<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/luxx0zeko.css';
import '../../css/o/oc-e4mb7v.css';
import '../../css/i/i8e6vr1if.css';
import '../../css/w/wut-a81uk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="luxx0zeko"/><path clip-rule="evenodd" class="oc-e4mb7v"/><path class="i8e6vr1if"/><path clip-rule="evenodd" class="wut-a81uk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:ab-testing-solid" {...props}></Icon>
