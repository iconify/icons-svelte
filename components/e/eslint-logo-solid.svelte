<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qxa7gactv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qxa7gactv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:eslint-logo-solid" {...props}></Icon>
