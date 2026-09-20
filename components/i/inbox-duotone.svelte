<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mbjt7ebfi.css';
import '../../css/j/jhxqmf5zh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mbjt7ebfi"/><path class="jhxqmf5zh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:inbox-duotone" {...props}></Icon>
