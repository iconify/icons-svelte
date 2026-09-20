<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eosxhobfh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eosxhobfh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:relation-zero-or-one-to-one-or-many" {...props}></Icon>
