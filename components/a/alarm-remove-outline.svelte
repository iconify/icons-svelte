<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/il8m2xbwe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="il8m2xbwe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:alarm-remove-outline" {...props}></Icon>
