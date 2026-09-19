<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uzqxore6r.css';
import '../../css/i/i6-ceabdw.css';
import '../../css/i/itgcd8bme.css';
import '../../css/p/p6-i0mbfr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<circle class="uzqxore6r"/><path class="i6-ceabdw"/><circle class="itgcd8bme"/><path class="p6-i0mbfr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-switch" {...props}></Icon>
