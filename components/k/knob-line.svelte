<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cwowkw2ww.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cwowkw2ww"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:knob-line" {...props}></Icon>
