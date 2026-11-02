<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qbjfk5bks.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qbjfk5bks"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:cloud-backup-fill" {...props}></Icon>
