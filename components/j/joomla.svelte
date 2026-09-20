<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/muz_ezbtz.css';
import '../../css/w/w21ld6b4s.css';
import '../../css/k/kxk-2wido.css';
import '../../css/n/n2j8p5b2m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="muz_ezbtz"/><path class="w21ld6b4s"/><path class="kxk-2wido"/><path class="n2j8p5b2m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:joomla" {...props}></Icon>
