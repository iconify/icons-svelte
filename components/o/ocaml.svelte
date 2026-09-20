<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dsfdawbzr.css';
import '../../css/s/sghc7ijwi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dsfdawbzr"/><path class="sghc7ijwi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:ocaml" {...props}></Icon>
