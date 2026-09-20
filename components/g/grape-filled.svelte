<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dy6yqbbtn.css';
import '../../css/c/ceo0jccjy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dy6yqbbtn"/><path class="ceo0jccjy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:grape-filled" {...props}></Icon>
