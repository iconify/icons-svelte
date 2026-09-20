<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/djdujaclh.css';
import '../../css/p/pgkbw5buh.css';
import '../../css/e/eklvps3uq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="djdujaclh"/><path class="pgkbw5buh"/><path class="eklvps3uq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:envelope-at-light" {...props}></Icon>
