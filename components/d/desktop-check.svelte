<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t8dem8bar.css';
import '../../css/g/gyqp2acas.css';
import '../../css/j/jvoh6cbav.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="t8dem8bar"/><path clip-rule="evenodd" class="gyqp2acas"/><path class="jvoh6cbav"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:desktop-check" {...props}></Icon>
