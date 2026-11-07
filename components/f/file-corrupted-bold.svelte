<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rhj7tk-5q.css';
import '../../css/c/cvj_c0b3m.css';
import '../../css/n/nqjdsphxz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rhj7tk-5q"/><path class="cvj_c0b3m"/><path class="nqjdsphxz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:file-corrupted-bold" {...props}></Icon>
