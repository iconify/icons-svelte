<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q-3qc_bhv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="q-3qc_bhv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:flutter-logo-block" {...props}></Icon>
