<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bzjm_3bmj.css';
import '../../css/v/vun6ubbjw.css';
import '../../css/e/eyqpwsbyt.css';
import '../../css/o/o12pcgbwf.css';
import '../../css/i/i-07h4bkh.css';
import '../../css/i/i-ke3gyiz.css';
import '../../css/w/wqstgm7-t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="bzjm_3bmj"/><path class="vun6ubbjw"/><path class="eyqpwsbyt"/><path class="o12pcgbwf"/><path class="i-07h4bkh"/><path class="i-ke3gyiz"/><path class="wqstgm7-t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-barcode-outline" {...props}></Icon>
