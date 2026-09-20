<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mp9czab_u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mp9czab_u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:bill-list-bold" {...props}></Icon>
