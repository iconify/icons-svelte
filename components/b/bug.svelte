<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hlerm3brg.css';
import '../../css/m/mgar0-gjb.css';
import '../../css/z/zmfqa13ae.css';
import '../../css/p/puphvnb0h.css';
import '../../css/i/idjc4pbow.css';
import '../../css/l/lkzo6fybb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="hlerm3brg"/><path class="mgar0-gjb"/><path class="zmfqa13ae"/><path class="puphvnb0h"/><path class="idjc4pbow"/><path class="lkzo6fybb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:bug" {...props}></Icon>
