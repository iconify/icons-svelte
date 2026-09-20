<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ouaapzbuk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ouaapzbuk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:panel-right-sharp-fill" {...props}></Icon>
