<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/q/qhsvm2ywy.css';
import '../../css/g/ghrqsmb5n.css';
import '../../css/g/g6vnjnbpk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="qhsvm2ywy"/><path class="ghrqsmb5n"/><path class="g6vnjnbpk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="evicons:community-verified" {...props}></Icon>
