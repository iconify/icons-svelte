<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n913frb6j.css';
import '../../css/o/oxtj35b7v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="n913frb6j"/><path class="oxtj35b7v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:folder-lock-filled" {...props}></Icon>
