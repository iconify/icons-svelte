<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v5riosbee.css';
import '../../css/e/egqmiqysx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v5riosbee"/><path class="egqmiqysx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:color-picker-fill" {...props}></Icon>
