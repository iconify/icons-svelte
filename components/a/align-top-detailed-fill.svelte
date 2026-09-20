<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bzg60ubxn.css';
import '../../css/z/z4470fb2t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bzg60ubxn"/><path clip-rule="evenodd" class="z4470fb2t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:align-top-detailed-fill" {...props}></Icon>
