<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qnnw6covj.css';
import '../../css/r/rh07anbcy.css';
import '../../css/s/snp287xku.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="qnnw6covj"/><path class="rh07anbcy"/><path class="snp287xku"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-emojis:china" {...props}></Icon>
