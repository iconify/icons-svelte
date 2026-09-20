<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mje02xb7t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mje02xb7t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:kakao-talk-logo-block" {...props}></Icon>
