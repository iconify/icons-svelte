<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v6mz_vjes.css';
import '../../css/c/c441vmfnl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v6mz_vjes"/><path clip-rule="evenodd" class="c441vmfnl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bitcoin-icons:bank-filled" {...props}></Icon>
