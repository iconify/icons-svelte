<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ee3miprbq.css';
import '../../css/i/i64djg6ut.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ee3miprbq"/><path class="i64djg6ut"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:inbox-minus-fill" {...props}></Icon>
