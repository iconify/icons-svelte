<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nfj-kyfix.css';
import '../../css/j/j0hmkbc4a.css';
import '../../css/e/egn_sr01y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="nfj-kyfix"/><path clip-rule="evenodd" class="j0hmkbc4a"/><path clip-rule="evenodd" class="egn_sr01y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cuida:monitor-outline" {...props}></Icon>
