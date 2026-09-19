<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qzkh3bczm.css';
import '../../css/k/kic1kiyda.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path clip-rule="evenodd" class="qzkh3bczm"/><circle class="kic1kiyda"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flat-ui:magicmouse" {...props}></Icon>
