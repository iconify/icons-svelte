<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yzhi-ac4k.css';
import '../../css/c/ck99yo6hz.css';
import '../../css/g/gqyaulbpw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="yzhi-ac4k"/><path class="ck99yo6hz"/><path class="gqyaulbpw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:microsoft-powerpoint-light" {...props}></Icon>
