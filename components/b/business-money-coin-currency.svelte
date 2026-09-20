<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wesomf70y.css';
import '../../css/s/s71mep88y.css';
import '../../css/v/v5aq_m_zu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="wesomf70y"/><path class="s71mep88y"/><path class="v5aq_m_zu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:business-money-coin-currency" {...props}></Icon>
