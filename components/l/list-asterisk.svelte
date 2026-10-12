<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t-1ng1bws.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t-1ng1bws"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="andrsrxn:list-asterisk" {...props}></Icon>
