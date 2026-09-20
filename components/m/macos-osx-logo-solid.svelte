<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eeu22r-zw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eeu22r-zw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:macos-osx-logo-solid" {...props}></Icon>
