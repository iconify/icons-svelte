<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dwvqjfwul.css';
import '../../css/h/he6gs9bkw.css';
import '../../css/p/prs_noded.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dwvqjfwul"/><path class="he6gs9bkw"/><path class="prs_noded"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:git-compare-24" {...props}></Icon>
