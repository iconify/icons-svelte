<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n_z9o5mag.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="n_z9o5mag"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:elixir-logo-solid" {...props}></Icon>
