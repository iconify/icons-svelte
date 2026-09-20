<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bo_2v9b7x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":26,"height":26};
const content = `<path clip-rule="evenodd" class="bo_2v9b7x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wpf:android-os" {...props}></Icon>
