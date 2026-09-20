<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fwyel9bps.css';
import '../../css/v/vzf2kqbwe.css';
import '../../css/v/vyby-xbyp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="fwyel9bps"/><path class="vzf2kqbwe"/><path class="vyby-xbyp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:radicle-dark" {...props}></Icon>
