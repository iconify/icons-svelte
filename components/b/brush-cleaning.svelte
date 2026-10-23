<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mp0io-2sf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mp0io-2sf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:brush-cleaning" {...props}></Icon>
