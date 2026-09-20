<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a3suf8dlg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a3suf8dlg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:relation-zero-or-one-to-zero-or-many" {...props}></Icon>
