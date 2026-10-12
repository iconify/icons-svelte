<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cixtz2ice.css';
import '../../css/y/yo5kbeb8m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cixtz2ice"/><path class="yo5kbeb8m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:database-backup-filled" {...props}></Icon>
