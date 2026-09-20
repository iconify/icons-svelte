<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i2dkisrbn.css';
import '../../css/i/i483i_kue.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i2dkisrbn"/><path class="i483i_kue"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:phone-incoming-fill" {...props}></Icon>
