<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c7gntf5tm.css';
import '../../css/s/sbi9n7bck.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c7gntf5tm"/><path class="sbi9n7bck"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:hubble-exchange" {...props}></Icon>
