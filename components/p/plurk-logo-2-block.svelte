<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t91ubdc2t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="t91ubdc2t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:plurk-logo-2-block" {...props}></Icon>
