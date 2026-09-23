<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/evm-pg59v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="evm-pg59v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="meteor-icons:badge-percent" {...props}></Icon>
