<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n-z07utpj.css';
import '../../css/d/d2xkq0bie.css';
import '../../css/v/vc6oyzbtg.css';
import '../../css/y/ykk37hror.css';
import '../../css/x/xu-e9yfuh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="n-z07utpj"/><path class="d2xkq0bie"/><path class="vc6oyzbtg"/><path class="ykk37hror"/><path class="xu-e9yfuh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:cosmosdb" {...props}></Icon>
