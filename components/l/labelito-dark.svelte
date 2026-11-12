<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mvp3tpbju.css';
import '../../css/q/q36ormboe.css';
import '../../css/q/qoxxme1vj.css';
import '../../css/g/gcldfhbqv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="mvp3tpbju"/><path class="q36ormboe"/><path class="qoxxme1vj"/><path class="gcldfhbqv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:labelito-dark" {...props}></Icon>
