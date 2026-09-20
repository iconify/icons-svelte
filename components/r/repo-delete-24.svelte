<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/da9f7744f.css';
import '../../css/s/sj5wtjbpp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="da9f7744f"/><path class="sj5wtjbpp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:repo-delete-24" {...props}></Icon>
