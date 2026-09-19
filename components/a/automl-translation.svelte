<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dyd-5l9hj.css';
import '../../css/d/dko0y8bbo.css';
import '../../css/c/c-39a_bhy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dyd-5l9hj"/><path class="dko0y8bbo"/><path class="c-39a_bhy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gcp:automl-translation" {...props}></Icon>
