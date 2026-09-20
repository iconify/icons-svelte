<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fjq-1sd1r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="fjq-1sd1r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:device-database-encryption-1-remix" {...props}></Icon>
