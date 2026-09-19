<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h32t530tv.css';
import '../../css/h/hutuskbuc.css';
import '../../css/n/n9cednr3v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="h32t530tv"/><path class="hutuskbuc"/><path class="n9cednr3v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:disappointed" {...props}></Icon>
