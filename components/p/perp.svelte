<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/ds7fe3bxn.css';
import '../../css/s/svj3x-59u.css';
import '../../css/p/p5evhgbgk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ds7fe3bxn"/><path clip-rule="evenodd" class="svj3x-59u"/><path class="p5evhgbgk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:perp" {...props}></Icon>
